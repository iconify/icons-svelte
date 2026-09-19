<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b6b2j8btj.css';
import '../../css/w/wrweh8jcs.css';
import '../../css/h/ho0kx1xbu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="b6b2j8btj"/><path class="wrweh8jcs"/><path class="ho0kx1xbu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:database" {...props}></Icon>
