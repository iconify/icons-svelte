<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q_paa_jws.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q_paa_jws"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:face-smile-plus-solid" {...props}></Icon>
