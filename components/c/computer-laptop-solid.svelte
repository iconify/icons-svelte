<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tlixmjufr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tlixmjufr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:computer-laptop-solid" {...props}></Icon>
