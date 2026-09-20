<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pqmpyebxv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pqmpyebxv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:pin-fill" {...props}></Icon>
