<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jas9_-b0f.css';
import '../../css/h/hf3ru2_zl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="duoicon-secondary-layer jas9_-b0f"/><path class="duoicon-primary-layer hf3ru2_zl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="duo-icons:alert-triangle" {...props}></Icon>
