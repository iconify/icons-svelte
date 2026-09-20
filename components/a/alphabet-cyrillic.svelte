<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o-y_ncckj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o-y_ncckj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:alphabet-cyrillic" {...props}></Icon>
