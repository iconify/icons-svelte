<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s99ga2boz.css';
import '../../css/m/maw0v5bht.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="duoicon-secondary-layer s99ga2boz"/><path class="duoicon-primary-layer maw0v5bht"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="duo-icons:chip" {...props}></Icon>
