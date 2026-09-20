<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g3bvu71xf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="g3bvu71xf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nonicons:capacitor-16" {...props}></Icon>
