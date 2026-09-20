<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/krhh1nj_a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="krhh1nj_a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:radio" {...props}></Icon>
