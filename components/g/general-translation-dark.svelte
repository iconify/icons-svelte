<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b0o537bra.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":215.696,"height":215.696,"left":20.152,"top":20.152};
const content = `<path class="b0o537bra"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:general-translation-dark" {...props}></Icon>
