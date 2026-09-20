<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/afmg7javi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="afmg7javi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:brand-visa" {...props}></Icon>
