<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wgjp5_b_u.css';
import '../../css/w/w1hfhybdb.css';
import '../../css/e/ecqzus6uh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="wgjp5_b_u"/><path class="w1hfhybdb"/><path class="ecqzus6uh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:marker-substation-20" {...props}></Icon>
