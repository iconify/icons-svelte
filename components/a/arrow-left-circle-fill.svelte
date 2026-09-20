<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uk2674f5h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="uk2674f5h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:arrow-left-circle-fill" {...props}></Icon>
