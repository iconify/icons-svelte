<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/c/c-jn_38_e.css';
import '../../css/b/be6sunbbx.css';
import '../../css/y/yut10vb4w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="c-jn_38_e"/><path class="be6sunbbx"/><path class="yut10vb4w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:message-notification-02" {...props}></Icon>
