<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lfyooabog.css';
import '../../css/g/gxd-8e_9n.css';
import '../../css/m/mjkpimbqx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lfyooabog"/><path class="gxd-8e_9n"/><path class="mjkpimbqx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:article-alt-duotone" {...props}></Icon>
