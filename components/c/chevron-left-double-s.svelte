<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lda1ajbqk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lda1ajbqk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:chevron-left-double-s" {...props}></Icon>
