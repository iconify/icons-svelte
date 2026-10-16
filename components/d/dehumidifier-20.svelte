<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gqfw9ounj.css';
import '../../css/i/ibxubn_yy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="gqfw9ounj"/><path class="ibxubn_yy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:dehumidifier-20" {...props}></Icon>
