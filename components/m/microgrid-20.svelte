<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/thf03bbvf.css';
import '../../css/i/i1ehzlbeu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="thf03bbvf"/><path class="i1ehzlbeu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:microgrid-20" {...props}></Icon>
