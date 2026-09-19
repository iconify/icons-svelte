<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ybjym5b1h.css';
import '../../css/b/bjzsqyhqp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="duoicon-secondary-layer ybjym5b1h"/><path class="bjzsqyhqp duoicon-primary-layer"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="duo-icons:bell-badge" {...props}></Icon>
