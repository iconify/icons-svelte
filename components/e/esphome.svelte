<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qi3-pkb_c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qi3-pkb_c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:esphome" {...props}></Icon>
