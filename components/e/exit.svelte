<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wjk7blide.css';
import '../../css/t/tfmdi36dd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wjk7blide"/><path class="tfmdi36dd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:exit" {...props}></Icon>
