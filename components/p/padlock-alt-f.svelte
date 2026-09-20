<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zrl-cic7i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-6,"top":-2};
const content = `<path class="zrl-cic7i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:padlock-alt-f" {...props}></Icon>
