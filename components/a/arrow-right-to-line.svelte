<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lnl-5nbrw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="lnl-5nbrw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:arrow-right-to-line" {...props}></Icon>
