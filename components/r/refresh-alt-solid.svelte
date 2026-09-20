<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eq26h3bso.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="eq26h3bso"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:refresh-alt-solid" {...props}></Icon>
