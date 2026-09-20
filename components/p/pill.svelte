<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z5a3lk7dv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z5a3lk7dv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:pill" {...props}></Icon>
