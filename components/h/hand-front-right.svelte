<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dvit73bpe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dvit73bpe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:hand-front-right" {...props}></Icon>
