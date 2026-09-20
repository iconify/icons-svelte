<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oks3pobcd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="oks3pobcd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:play-next-fill" {...props}></Icon>
