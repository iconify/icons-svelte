<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vu11w07_v.css';
import '../../css/f/f0yad6-af.css';
import '../../css/c/cq_2o7u8v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vu11w07_v"/><path class="f0yad6-af"/><path clip-rule="evenodd" class="cq_2o7u8v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:bone-broken-outline" {...props}></Icon>
