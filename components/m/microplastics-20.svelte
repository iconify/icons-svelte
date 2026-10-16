<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kf-q9zggw.css';
import '../../css/y/y4-jdzhel.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="kf-q9zggw"/><path class="y4-jdzhel"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:microplastics-20" {...props}></Icon>
