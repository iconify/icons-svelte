<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pfs3dk6ul.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pfs3dk6ul"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:clipboard-fill" {...props}></Icon>
