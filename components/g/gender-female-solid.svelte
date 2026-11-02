<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bnbnafbzk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bnbnafbzk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:gender-female-solid" {...props}></Icon>
