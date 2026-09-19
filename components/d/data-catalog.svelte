<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o1fomeb2x.css';
import '../../css/i/ie06e3b6z.css';
import '../../css/t/tie69u5xw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o1fomeb2x"/><path class="ie06e3b6z"/><path class="tie69u5xw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gcp:data-catalog" {...props}></Icon>
