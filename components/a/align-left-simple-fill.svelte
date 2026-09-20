<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fqtmz3b1d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fqtmz3b1d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:align-left-simple-fill" {...props}></Icon>
