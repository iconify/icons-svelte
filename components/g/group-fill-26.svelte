<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gqgn4v-kd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<path class="gqgn4v-kd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:group-fill-26" {...props}></Icon>
