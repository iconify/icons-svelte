<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/km11tn.css';
import '../../css/y/ydovum.css';
import '../../css/j/jerajh.css';
import '../../css/b/bqezkf.css';
import '../../css/d/d-y0k17z.css';
import '../../css/d/d-eo5vsf.css';
import '../../css/d/d-hy4_ez.css';
import '../../css/d/d-zqf0qv.css';
import '../../css/d/d-h1s04y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="km11tn ydovum"/><path class="jerajh ydovum"/><path class="bqezkf ydovum"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:peertube-alt" {...props}></Icon>
