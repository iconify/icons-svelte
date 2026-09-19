<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cm0pbmbno.css';
import '../../css/o/o_b_sl5zu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="cm0pbmbno"/><path class="o_b_sl5zu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:ansible-lint" {...props}></Icon>
