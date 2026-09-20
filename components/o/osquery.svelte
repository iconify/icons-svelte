<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":255};
const content = `<path class="sd9u29uny"/><path class="f4_2imb2p"/><path class="dyf295bks"/><path class="lnf_v1bdb"/><path class="a2ez2ybll"/><path class="n3av71ups"/><path class="ssbzevbmn"/><path class="srzltpblf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="logos:osquery" {...props}></Icon>
<style>
:global(.a2ez2ybll) {
  fill: var(--svg-color--a596ff, #a596ff);
  d: path("M.801 254.936V191.2l63.605-63.605v63.869z");
}

:global(.dyf295bks) {
  fill: var(--svg-color--a596ff, #a596ff);
  d: path("M255.346 254.804H191.61l-63.605-63.605h63.867z");
}

:global(.f4_2imb2p) {
  d: path("M128.006.258v63.736l63.605 63.605v-63.87z");
}

:global(.lnf_v1bdb) {
  d: path("M255.346 127.595H191.61L128.005 191.2h63.867z");
}

:global(.n3av71ups) {
  d: path("M128.01 254.936V191.2l-63.605-63.605v63.869z");
}

:global(.sd9u29uny) {
  fill: var(--svg-color--a596ff, #a596ff);
  d: path("M255.215.258v63.736l-63.605 63.605v-63.87z");
}

:global(.srzltpblf) {
  d: path("M.672 127.594h63.736l63.605-63.605H64.145z");
}

:global(.ssbzevbmn) {
  fill: var(--svg-color--a596ff, #a596ff);
  d: path("M.672.386h63.736l63.605 63.605H64.145z");
}

</style>
