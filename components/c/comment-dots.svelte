<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dftf9rvck.css';
import '../../css/y/yin69t93p.css';
import '../../css/s/stjv0pdcv.css';
import '../../css/a/a11bti4rf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<circle class="dftf9rvck"/><path class="yin69t93p"/><circle class="stjv0pdcv"/><circle class="a11bti4rf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:comment-dots" {...props}></Icon>
