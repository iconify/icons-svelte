<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qd20b1j9f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qd20b1j9f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:arrow-up-right-circle-fill" {...props}></Icon>
