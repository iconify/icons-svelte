<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jyc322s0u.css';
import '../../css/j/jml6rubew.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jyc322s0u"/><path class="jml6rubew"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="akar-icons:django-fill" {...props}></Icon>
