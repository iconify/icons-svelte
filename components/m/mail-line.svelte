<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jku9oud5t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jku9oud5t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:mail-line" {...props}></Icon>
