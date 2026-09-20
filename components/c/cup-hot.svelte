<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v_0fh_zup.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="v_0fh_zup"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:cup-hot" {...props}></Icon>
