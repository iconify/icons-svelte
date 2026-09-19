<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s2sandlqm.css';
import '../../css/x/xgtqlm-cw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="duoicon-secondary-layer s2sandlqm"/><path class="duoicon-primary-layer xgtqlm-cw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="duo-icons:file" {...props}></Icon>
