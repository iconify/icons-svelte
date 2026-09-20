<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qa-o7h.css';
import '../../css/t/taf2xz.css';
import '../../css/w/wc7n7b.css';
import '../../css/e/ecu16w.css';
import '../../css/f/fequ5n.css';
import '../../css/s/so-to-12.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qa-o7h taf2xz wc7n7b"/><path class="ecu16w qa-o7h"/><path class="fequ5n qa-o7h taf2xz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:clipboard-check-to-clipboard-transition" {...props}></Icon>
