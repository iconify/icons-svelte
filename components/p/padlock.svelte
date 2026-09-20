<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b1ihjzb5j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-5,"top":-2};
const content = `<path class="b1ihjzb5j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:padlock" {...props}></Icon>
