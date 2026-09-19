<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vd7n89blv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<path class="vd7n89blv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:credit-card-26" {...props}></Icon>
