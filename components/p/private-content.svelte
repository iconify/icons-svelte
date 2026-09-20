<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b-srhgbjw.css';
import '../../css/i/io-ksobwe.css';
import '../../css/d/dhxhj3byh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b-srhgbjw"/><path class="io-ksobwe"/><path class="dhxhj3byh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:private-content" {...props}></Icon>
