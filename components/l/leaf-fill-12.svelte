<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g973qacms.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="g973qacms"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:leaf-fill-12" {...props}></Icon>
