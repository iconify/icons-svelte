<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fzgea5uph.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fzgea5uph"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:relation-one-to-many" {...props}></Icon>
