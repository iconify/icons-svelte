<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l33hdlfbw.css';
import '../../css/x/x_lq2pb5l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l33hdlfbw"/><path class="x_lq2pb5l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:mirror-2-bold" {...props}></Icon>
