<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dsc6fq3ty.css';
import '../../css/s/skmwvibla.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1000,"height":1000};
const content = `<circle class="dsc6fq3ty"/><path class="skmwvibla"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:mongo-express" {...props}></Icon>
