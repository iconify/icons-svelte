<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vyh6w9b_y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="vyh6w9b_y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:block-one" {...props}></Icon>
