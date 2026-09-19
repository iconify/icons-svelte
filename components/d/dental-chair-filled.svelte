<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vtlbrsb9b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vtlbrsb9b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:dental-chair-filled" {...props}></Icon>
