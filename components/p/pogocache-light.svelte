<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mq29v9bsn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mq29v9bsn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:pogocache-light" {...props}></Icon>
