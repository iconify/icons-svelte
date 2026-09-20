<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gmbolmbel.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="gmbolmbel"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:car-beside-person-sleeping-in-bed" {...props}></Icon>
