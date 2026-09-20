<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/weubr0vdq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="weubr0vdq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:marker-light" {...props}></Icon>
