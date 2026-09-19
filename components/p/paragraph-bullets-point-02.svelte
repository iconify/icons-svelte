<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/o/oe7vz9bcj.css';
import '../../css/t/t-7lz5bmz.css';
import '../../css/y/yphewc7qd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="oe7vz9bcj"/><circle class="t-7lz5bmz"/><circle class="yphewc7qd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:paragraph-bullets-point-02" {...props}></Icon>
