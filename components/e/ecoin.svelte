<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g7gzr4wdh.css';
import '../../css/w/w-1bkb7vd.css';
import '../../css/w/w22a27rwn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="g7gzr4wdh"/><path class="w-1bkb7vd"/><path class="w22a27rwn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:ecoin" {...props}></Icon>
