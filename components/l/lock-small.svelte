<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/beqkjnbmv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="beqkjnbmv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wordpress:lock-small" {...props}></Icon>
