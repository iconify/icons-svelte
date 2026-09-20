<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fs0didbcc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fs0didbcc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:logo-wecom" {...props}></Icon>
