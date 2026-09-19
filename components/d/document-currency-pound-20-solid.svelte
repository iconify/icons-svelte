<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cqn1lpbcn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="cqn1lpbcn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:document-currency-pound-20-solid" {...props}></Icon>
