<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ifod5ubje.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ifod5ubje"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:repeat-once" {...props}></Icon>
