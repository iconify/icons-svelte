<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eoy4dks5r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="eoy4dks5r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:guitar" {...props}></Icon>
