<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k413-ia3f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":520,"height":512};
const content = `<path class="k413-ia3f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:piggy-bank-coins" {...props}></Icon>
