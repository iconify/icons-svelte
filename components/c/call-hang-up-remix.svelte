<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s3y-_lbkk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="s3y-_lbkk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:call-hang-up-remix" {...props}></Icon>
