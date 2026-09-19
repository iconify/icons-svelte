<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s-wvqqbgn.css';
import '../../css/k/k6cv4hiap.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s-wvqqbgn"/><path clip-rule="evenodd" class="k6cv4hiap"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:flask-outline" {...props}></Icon>
