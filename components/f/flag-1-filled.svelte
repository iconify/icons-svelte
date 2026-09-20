<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1pqwkvuw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n1pqwkvuw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:flag-1-filled" {...props}></Icon>
