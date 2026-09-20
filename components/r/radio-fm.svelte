<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tcmrx9q_v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tcmrx9q_v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:radio-fm" {...props}></Icon>
