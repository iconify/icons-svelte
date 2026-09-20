<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bnsnku.css';
import '../../css/q/qa-o7h.css';
import '../../css/f/f2o4kw.css';
import '../../css/s/so-from-66.css';
import '../../css/s/so-to-0.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bnsnku qa-o7h"/><path class="f2o4kw qa-o7h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:clipboard" {...props}></Icon>
