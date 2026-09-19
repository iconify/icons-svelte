<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r8p9k171u.css';
import '../../css/x/xx72yyb6l.css';
import '../../css/o/ovoprwbgx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="r8p9k171u"/><path class="xx72yyb6l"/><path class="ovoprwbgx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-tv" {...props}></Icon>
