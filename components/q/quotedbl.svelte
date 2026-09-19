<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mp_ca1b9g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":262,"height":723};
const content = `<path class="mp_ca1b9g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:quotedbl" {...props}></Icon>
