<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lt8wifbth.css';
import '../../css/k/kdpqefbdy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lt8wifbth"/><path class="kdpqefbdy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:creditcard-add-filled" {...props}></Icon>
