<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ae22v_bnk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ae22v_bnk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:comment-arrow-right-outline" {...props}></Icon>
