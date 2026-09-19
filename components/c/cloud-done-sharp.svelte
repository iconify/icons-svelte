<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pmaaj5vii.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pmaaj5vii"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:cloud-done-sharp" {...props}></Icon>
