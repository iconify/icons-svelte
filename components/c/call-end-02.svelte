<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y51jpykkk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y51jpykkk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:call-end-02" {...props}></Icon>
