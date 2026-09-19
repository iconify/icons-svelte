<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kzug-_pza.css';
import '../../css/p/pknasvape.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kzug-_pza"/><path class="pknasvape"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:explore-solid" {...props}></Icon>
