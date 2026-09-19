<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i14yeqg2f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="i14yeqg2f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:dotproject" {...props}></Icon>
