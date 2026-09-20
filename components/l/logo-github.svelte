<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bhpx4tbiq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bhpx4tbiq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:logo-github" {...props}></Icon>
