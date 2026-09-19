<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pjsseubff.css';
import '../../css/p/p9m7uqziz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="duoicon-secondary-layer pjsseubff"/><path class="duoicon-primary-layer p9m7uqziz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="duo-icons:message-2" {...props}></Icon>
