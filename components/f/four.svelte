<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a272yoahj.css';
import '../../css/x/x51ruxbqo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a272yoahj"/><path clip-rule="evenodd" class="x51ruxbqo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:four" {...props}></Icon>
