<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v1zm2n9fx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<path class="v1zm2n9fx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:app-26" {...props}></Icon>
