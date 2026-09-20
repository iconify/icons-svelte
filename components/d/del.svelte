<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mkah51bta.css';
import '../../css/h/h5gugn-ip.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="mkah51bta"/><path class="h5gugn-ip"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:del" {...props}></Icon>
