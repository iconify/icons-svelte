<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r9m217b_a.css';
import '../../css/a/azvvpmbsy.css';
import '../../css/h/hk39bac5y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="r9m217b_a"/><path class="azvvpmbsy"/><path class="hk39bac5y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:printer-20" {...props}></Icon>
