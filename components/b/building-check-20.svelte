<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h1kol59_x.css';
import '../../css/w/wk-mpkb0v.css';
import '../../css/g/g3z_62mfz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="h1kol59_x"/><path class="wk-mpkb0v"/><path class="g3z_62mfz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:building-check-20" {...props}></Icon>
