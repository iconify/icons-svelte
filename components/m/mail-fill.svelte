<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rnnzl5bdg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rnnzl5bdg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:mail-fill" {...props}></Icon>
