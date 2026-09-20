<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a_pc7cb8z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a_pc7cb8z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:arrow-big-left-dash" {...props}></Icon>
