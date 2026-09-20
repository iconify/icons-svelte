<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r8z8e9buc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r8z8e9buc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:replace-user" {...props}></Icon>
