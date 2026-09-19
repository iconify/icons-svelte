<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kwpj8qbfr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kwpj8qbfr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:mobile-ring-filled" {...props}></Icon>
