<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tq_y27ygp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tq_y27ygp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="akar-icons:hashtag" {...props}></Icon>
