<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pih1z72mh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pih1z72mh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:bag-check-bold" {...props}></Icon>
