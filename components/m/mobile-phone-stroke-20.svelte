<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k9so18btn.css';
import '../../css/q/qlx4k6bgd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="k9so18btn"/><path class="qlx4k6bgd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:mobile-phone-stroke-20" {...props}></Icon>
