<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/am-bkj_kg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="am-bkj_kg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:bar-stool" {...props}></Icon>
