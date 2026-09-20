<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/ha4662b3c.css';
import '../../css/k/kn0-ukb4s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ha4662b3c"/><path clip-rule="evenodd" class="kn0-ukb4s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:archive-16" {...props}></Icon>
