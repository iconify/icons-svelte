<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wpwwd192v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="wpwwd192v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:clock" {...props}></Icon>
