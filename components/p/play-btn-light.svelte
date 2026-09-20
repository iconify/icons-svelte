<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dkuff2bgq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dkuff2bgq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:play-btn-light" {...props}></Icon>
