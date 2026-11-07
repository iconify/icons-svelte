<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yyu_2jbbj.css';
import '../../css/h/hh3uuxn4j.css';
import '../../css/h/hk6-kiz3s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yyu_2jbbj"/><path class="hh3uuxn4j"/><path clip-rule="evenodd" class="hk6-kiz3s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:radio-bold" {...props}></Icon>
