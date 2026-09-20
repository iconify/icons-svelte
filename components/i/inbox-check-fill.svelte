<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ee3miprbq.css';
import '../../css/y/yjr4r8bte.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ee3miprbq"/><path class="yjr4r8bte"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:inbox-check-fill" {...props}></Icon>
