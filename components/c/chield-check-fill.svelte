<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aunnx6las.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="aunnx6las"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:chield-check-fill" {...props}></Icon>
