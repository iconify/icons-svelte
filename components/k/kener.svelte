<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ya79xjbtw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ya79xjbtw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:kener" {...props}></Icon>
