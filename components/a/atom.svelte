<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dcmrdvhow.css';
import '../../css/h/hzunv164j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dcmrdvhow"/><path class="hzunv164j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:atom" {...props}></Icon>
