<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pr_vn-bin.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-1.5};
const content = `<path class="pr_vn-bin"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:help-f" {...props}></Icon>
