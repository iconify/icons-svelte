<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z2833rb_h.css';
import '../../css/m/mwapz_r-l.css';
import '../../css/r/rxcdkqb9f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="z2833rb_h"/><path class="mwapz_r-l"/><path class="rxcdkqb9f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:ladybird-20" {...props}></Icon>
