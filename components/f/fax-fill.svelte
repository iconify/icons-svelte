<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zd2oewbxg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zd2oewbxg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:fax-fill" {...props}></Icon>
